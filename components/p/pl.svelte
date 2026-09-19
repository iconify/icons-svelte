<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/neymbdbaf.css';
import '../../css/p/p14c00v9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":189};
const content = `<g class="ft5dv1b6b"><path class="neymbdbaf"/><path class="p14c00v9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:pl" {...props}></Icon>
