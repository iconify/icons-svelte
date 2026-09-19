<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ywrrljb0f.css';
import '../../css/f/fqx9w60ay.css';
import '../../css/a/a53m6sb5f.css';
import '../../css/s/sclvgt7mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ywrrljb0f"/><path class="fqx9w60ay"/><path class="a53m6sb5f"/><path class="sclvgt7mn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rocket-duo" {...props}></Icon>
