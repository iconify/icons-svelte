<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd191wbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd191wbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-nfc-off" {...props}></Icon>
