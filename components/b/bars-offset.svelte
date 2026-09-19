<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/l/le8r1fb7t.css';
import '../../css/z/z8_yi4bim.css';
import '../../css/j/jv95subdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="le8r1fb7t"/><path class="z8_yi4bim"/><path class="jv95subdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bars-offset" {...props}></Icon>
