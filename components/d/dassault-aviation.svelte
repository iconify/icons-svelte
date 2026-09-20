<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi0vm5zlg.css';
import '../../css/w/w5p8r3ckd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1547,"height":2503};
const content = `<path class="pi0vm5zlg"/><path class="w5p8r3ckd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dassault-aviation" {...props}></Icon>
