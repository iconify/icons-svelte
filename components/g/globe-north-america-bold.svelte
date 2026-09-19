<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bpin_ybto.css';
import '../../css/b/boa-geyjv.css';
import '../../css/n/nt_zo_p2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bpin_ybto"/><path clip-rule="evenodd" class="boa-geyjv"/><path class="nt_zo_p2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-north-america-bold" {...props}></Icon>
