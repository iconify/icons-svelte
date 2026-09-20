<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx3-p01if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx3-p01if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-down-right-line" {...props}></Icon>
