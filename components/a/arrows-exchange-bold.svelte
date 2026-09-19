<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pmzqopkvq.css';
import '../../css/o/o4gk2is8h.css';
import '../../css/c/cumbvnb-s.css';
import '../../css/y/yjkv3pplf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="pmzqopkvq"/><path class="o4gk2is8h"/><path class="cumbvnb-s"/><path class="yjkv3pplf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-exchange-bold" {...props}></Icon>
