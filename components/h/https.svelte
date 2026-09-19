<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbhtpfbxo.css';
import '../../css/d/dv2xvhb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbhtpfbxo"/><path class="dv2xvhb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:https" {...props}></Icon>
