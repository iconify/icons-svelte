<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwlmx-b3y.css';
import '../../css/d/dlg1f9bpn.css';
import '../../css/v/vioal8b1j.css';
import '../../css/p/p_2y21whp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zwlmx-b3y"/><path class="dlg1f9bpn"/><path class="vioal8b1j"/><path class="p_2y21whp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:mint" {...props}></Icon>
