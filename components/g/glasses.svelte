<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/alo70ezch.css';
import '../../css/w/wwhsvn6bz.css';
import '../../css/x/x8-viqewl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="alo70ezch"/><circle class="wwhsvn6bz"/><path class="x8-viqewl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:glasses" {...props}></Icon>
