<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs-1v6bed.css';
import '../../css/x/x4a8ysb7l.css';
import '../../css/w/wkchaul0v.css';
import '../../css/d/dw16-vbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hs-1v6bed"/><path class="x4a8ysb7l"/><path class="wkchaul0v"/><path class="dw16-vbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bench-vice-48-bold" {...props}></Icon>
