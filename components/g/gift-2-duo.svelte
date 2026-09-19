<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d3-609uay.css';
import '../../css/q/qg1124b7z.css';
import '../../css/g/ggyc5ns_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="d3-609uay"/><path class="qg1124b7z"/><path class="ggyc5ns_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:gift-2-duo" {...props}></Icon>
