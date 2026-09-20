<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_mt3gbpw.css';
import '../../css/t/twwlo65xz.css';
import '../../css/y/ytc8wppym.css';
import '../../css/j/jmon4qjrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGmAhx2dHO)"><path class="c_mt3gbpw"/><path clip-rule="evenodd" class="twwlo65xz"/><path clip-rule="evenodd" class="ytc8wppym"/></g><defs><clipPath id="SVGmAhx2dHO"><path class="jmon4qjrz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:robohelp-server" {...props}></Icon>
