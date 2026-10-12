<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrjmwob1j.css';
import '../../css/g/gbt6yvbgo.css';
import '../../css/u/u95awmdai.css';
import '../../css/n/n4gxhbcfl.css';
import '../../css/n/naj2oabkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xrjmwob1j"/><path class="gbt6yvbgo"/><path class="u95awmdai"/><path class="n4gxhbcfl"/><path class="naj2oabkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:printer-3d-20-bold" {...props}></Icon>
