<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciqskgrxn.css';
import '../../css/c/c5a_m3jtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="ciqskgrxn"/><circle class="c5a_m3jtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:full-moon" {...props}></Icon>
