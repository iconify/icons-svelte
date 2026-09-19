<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s51y5no9m.css';
import '../../css/q/q9d8uuvac.css';
import '../../css/h/h00g_jboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="s51y5no9m"/><path class="q9d8uuvac"/><path class="h00g_jboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layer-plus-duo" {...props}></Icon>
