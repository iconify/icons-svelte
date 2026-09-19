<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcc50sb7a.css';
import '../../css/o/od2-gdbso.css';
import '../../css/e/esc0vsbcl.css';
import '../../css/v/vc-7i1ihb.css';
import '../../css/g/gj5k14bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wcc50sb7a"><rect class="od2-gdbso"/><rect class="esc0vsbcl"/><rect class="vc-7i1ihb"/><rect class="gj5k14bhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ellipsis-square-bold" {...props}></Icon>
