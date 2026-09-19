<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7mn_xgnv.css';
import '../../css/q/qcums4bin.css';
import '../../css/u/u0h4nqdfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="h7mn_xgnv"><path class="qcums4bin"/><path class="u0h4nqdfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-outline" {...props}></Icon>
