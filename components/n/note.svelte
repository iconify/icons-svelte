<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/ru3n1acww.css';
import '../../css/l/lgzmhqtyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="s9cl3zbei"><rect class="ru3n1acww"/><path class="lgzmhqtyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:note" {...props}></Icon>
