<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vznod2tgq.css';
import '../../css/g/gufa1abqb.css';
import '../../css/i/i_6ts1ome.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="vznod2tgq"/><path class="gufa1abqb"/><path class="i_6ts1ome"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:browser-edge" {...props}></Icon>
