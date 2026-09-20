<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3824eb3w.css';
import '../../css/u/u5_58bctg.css';
import '../../css/k/kpmaaubsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="l3824eb3w"/><path class="u5_58bctg"/><path class="kpmaaubsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:glass-of-milk" {...props}></Icon>
