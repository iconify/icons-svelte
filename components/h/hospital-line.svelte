<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plc_te-wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plc_te-wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hospital-line" {...props}></Icon>
