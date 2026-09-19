<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt0u4kb6g.css';
import '../../css/z/zsooyfbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt0u4kb6g"/><path class="zsooyfbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:pie-chart-alt-2" {...props}></Icon>
