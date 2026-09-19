<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn3dr3d8s.css';
import '../../css/l/l5yoditpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn3dr3d8s"/><circle class="l5yoditpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-disc" {...props}></Icon>
