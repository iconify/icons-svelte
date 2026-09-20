<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu3t0ac_w.css';
import '../../css/u/uobch0qxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu3t0ac_w"/><path class="uobch0qxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:color-spray" {...props}></Icon>
