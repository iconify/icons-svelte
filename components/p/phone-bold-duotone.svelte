<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnl-77aoj.css';
import '../../css/w/wsnzclbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnl-77aoj"/><path class="wsnzclbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-bold-duotone" {...props}></Icon>
