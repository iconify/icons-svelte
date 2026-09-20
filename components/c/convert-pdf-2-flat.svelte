<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iubb9-b0f.css';
import '../../css/m/mo-6exyaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="iubb9-b0f"/><path clip-rule="evenodd" class="mo-6exyaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:convert-pdf-2-flat" {...props}></Icon>
