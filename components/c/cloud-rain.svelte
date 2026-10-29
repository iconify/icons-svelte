<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l12p6vo3k.css';
import '../../css/q/qqmov0t5w.css';
import '../../css/l/l5ay5lbvr.css';
import '../../css/z/z15avum9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l12p6vo3k wm-k"/><path class="qqmov0t5w wm-k"/><path class="l5ay5lbvr wm-a"/><path class="wm-a z15avum9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:cloud-rain" {...props}></Icon>
