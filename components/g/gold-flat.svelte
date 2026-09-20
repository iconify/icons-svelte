<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnxi2rbnm.css';
import '../../css/g/g7dt3p6dr.css';
import '../../css/c/cedyn8zij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="wnxi2rbnm"><path clip-rule="evenodd" class="g7dt3p6dr"/><path class="cedyn8zij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:gold-flat" {...props}></Icon>
