<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wj4kpac6w.css';
import '../../css/w/w_nswibwm.css';
import '../../css/p/p7p95v0fb.css';
import '../../css/d/djam5bcdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g transform="translate(0 3)" class="n1lsf0bnc"><circle class="wj4kpac6w"/><ellipse class="w_nswibwm"/><ellipse class="p7p95v0fb"/><path class="djam5bcdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:christmas-mistletoe" {...props}></Icon>
