<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv01ucbgq.css';
import '../../css/b/bp49p9l1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bv01ucbgq"/><path class="bp49p9l1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:lizard" {...props}></Icon>
