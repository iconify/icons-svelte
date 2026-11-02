<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxpnv3bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxpnv3bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-add-line" {...props}></Icon>
