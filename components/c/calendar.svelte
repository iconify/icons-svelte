<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/p2fh9zbkx.css';
import '../../css/k/kwok6nb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><rect class="p2fh9zbkx"/><path class="kwok6nb8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:calendar" {...props}></Icon>
