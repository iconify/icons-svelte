<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_egubuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in_egubuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-center" {...props}></Icon>
