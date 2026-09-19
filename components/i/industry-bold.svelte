<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ngc5w1b_f.css';
import '../../css/s/slpd7bdal.css';
import '../../css/s/slwdzb4zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ngc5w1b_f"/><path class="slpd7bdal"/><path clip-rule="evenodd" class="slwdzb4zh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:industry-bold" {...props}></Icon>
