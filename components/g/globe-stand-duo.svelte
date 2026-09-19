<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t5oh21qle.css';
import '../../css/f/fweop44zq.css';
import '../../css/g/g57x7ynmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="t5oh21qle"/><path class="fweop44zq"/><path class="g57x7ynmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-duo" {...props}></Icon>
