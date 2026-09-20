<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxcyswb1d.css';
import '../../css/n/ndsn13p7t.css';
import '../../css/e/e2b_iy-oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxcyswb1d"/><path class="ndsn13p7t"/><path class="e2b_iy-oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:instrument-electronic-keyboard" {...props}></Icon>
