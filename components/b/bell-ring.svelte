<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qk9tnbfio.css';
import '../../css/x/xphc7fb2u.css';
import '../../css/r/rod3izbjm.css';
import '../../css/h/hjg2nm81k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qk9tnbfio"/><path clip-rule="evenodd" class="xphc7fb2u"/><path clip-rule="evenodd" class="rod3izbjm"/><path class="hjg2nm81k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bell-ring" {...props}></Icon>
