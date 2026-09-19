<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls6_xn_4i.css';
import '../../css/z/zc3lmmbma.css';
import '../../css/x/xh1y7dbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="zc3lmmbma"/><path class="xh1y7dbbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:exe" {...props}></Icon>
