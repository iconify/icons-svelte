<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u1t0icc-v.css';
import '../../css/t/tfldu8b4b.css';
import '../../css/s/soqz66vtq.css';
import '../../css/k/k07x3y6kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="u1t0icc-v"/><path class="tfldu8b4b"/><path class="soqz66vtq"/><path class="k07x3y6kz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:musical-keyboard" {...props}></Icon>
