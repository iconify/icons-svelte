<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_mt3gbpw.css';
import '../../css/f/ff7_wib9n.css';
import '../../css/h/hnlzkbrjz.css';
import '../../css/j/jmon4qjrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGmAhx2dHO)"><path class="c_mt3gbpw"/><path clip-rule="evenodd" class="ff7_wib9n"/><path clip-rule="evenodd" class="hnlzkbrjz"/></g><defs><clipPath id="SVGmAhx2dHO"><path class="jmon4qjrz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:robohelp" {...props}></Icon>
