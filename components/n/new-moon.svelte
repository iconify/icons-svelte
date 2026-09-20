<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usozxnbrm.css';
import '../../css/u/u50yvab1y.css';
import '../../css/c/c5a_m3jtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="usozxnbrm"/><circle class="u50yvab1y"/><circle class="c5a_m3jtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:new-moon" {...props}></Icon>
