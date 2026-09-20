<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj9e8_bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj9e8_bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:more-2-fill" {...props}></Icon>
