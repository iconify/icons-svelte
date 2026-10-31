<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6fla5ihq.css';
import '../../css/w/wc3ev5p3f.css';
import '../../css/k/k6f9ajnvk.css';
import '../../css/f/fy2k2g21h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="q6fla5ihq"/><path class="wc3ev5p3f"/><path class="k6f9ajnvk"/><path class="fy2k2g21h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:djibouti" {...props}></Icon>
