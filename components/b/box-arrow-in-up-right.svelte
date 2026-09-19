<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r5fbmwldh.css';
import '../../css/s/sb0936ekk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="r5fbmwldh"/><path class="sb0936ekk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box-arrow-in-up-right" {...props}></Icon>
