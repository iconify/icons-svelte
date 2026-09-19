<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h6n2s7btu.css';
import '../../css/y/y0ima4i8y.css';
import '../../css/y/yi_45ddob.css';
import '../../css/a/asi2twp_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h6n2s7btu"/><path class="y0ima4i8y"/><path class="yi_45ddob"/><path class="asi2twp_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:pig-face" {...props}></Icon>
