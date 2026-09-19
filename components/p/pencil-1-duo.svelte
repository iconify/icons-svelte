<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ilt41gdzy.css';
import '../../css/h/ho8201-pa.css';
import '../../css/f/flrxrstck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ilt41gdzy"/><path class="ho8201-pa"/><path class="flrxrstck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pencil-1-duo" {...props}></Icon>
