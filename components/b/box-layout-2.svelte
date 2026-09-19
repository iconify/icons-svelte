<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/w/w_kllgnne.css';
import '../../css/u/upeavtbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><path class="w_kllgnne"/><path class="upeavtbgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-layout-2" {...props}></Icon>
