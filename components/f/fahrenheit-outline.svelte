<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ae6uo6b7p.css';
import '../../css/x/xtl2bkbxy.css';
import '../../css/h/h038b5hlx.css';
import '../../css/o/oxw8l6wad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ae6uo6b7p"/><path class="xtl2bkbxy"/><path clip-rule="evenodd" class="h038b5hlx"/><path class="oxw8l6wad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fahrenheit-outline" {...props}></Icon>
