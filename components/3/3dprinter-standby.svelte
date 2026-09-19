<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx_qx2rdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx_qx2rdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:3dprinter-standby" {...props}></Icon>
