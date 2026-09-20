<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5a4g0baj.css';
import '../../css/i/ifr7ntl_w.css';
import '../../css/c/csa2n4lwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="f5a4g0baj"/><path class="ifr7ntl_w"/><path class="csa2n4lwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:canoe" {...props}></Icon>
