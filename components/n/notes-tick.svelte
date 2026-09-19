<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c7nnx_bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><polyline points="7.25 14.25 2.75 14.25 2.75 1.75 13.25 1.75 13.25 9.25"/><path class="c7nnx_bxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:notes-tick" {...props}></Icon>
