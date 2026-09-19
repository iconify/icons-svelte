<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j42smtb5k.css';
import '../../css/j/juqffaboa.css';
import '../../css/r/rj0i6trac.css';
import '../../css/k/kc-5kvxmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="j42smtb5k"/><path class="juqffaboa"/><path class="rj0i6trac"/><path class="kc-5kvxmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-split-bold" {...props}></Icon>
