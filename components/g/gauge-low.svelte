<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkhrzpnvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkhrzpnvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gauge-low" {...props}></Icon>
