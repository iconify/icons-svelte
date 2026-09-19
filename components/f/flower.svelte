<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ollll1rvu.css';
import '../../css/s/ssk_xhn8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ollll1rvu"/><path class="ssk_xhn8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:flower" {...props}></Icon>
