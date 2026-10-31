<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kuuho-btb.css';
import '../../css/r/ruvbxe6ge.css';
import '../../css/u/upnry9bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kuuho-btb wm-k"/><path class="ruvbxe6ge wm-shine"/><path class="upnry9bsk wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:avatar-panda" {...props}></Icon>
