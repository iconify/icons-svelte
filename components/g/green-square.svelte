<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmfgqwb6s.css';
import '../../css/t/tbzab391z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fmfgqwb6s"/><path class="tbzab391z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:green-square" {...props}></Icon>
