<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ohqr0kb7r.css';
import '../../css/e/eivig8z_t.css';
import '../../css/p/pln1t8f_n.css';
import '../../css/w/wh8zg4byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ohqr0kb7r"/><path class="eivig8z_t"/><path class="pln1t8f_n"/><path class="wh8zg4byf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:bread" {...props}></Icon>
