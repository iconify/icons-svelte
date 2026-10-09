<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-g74icta.css';
import '../../css/p/pizowmb7j.css';
import '../../css/l/l525fxdrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="pizowmb7j"/><path class="l525fxdrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-download-20" {...props}></Icon>
