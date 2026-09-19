<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chnsk5b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chnsk5b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:board" {...props}></Icon>
