<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk3rxbbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk3rxbbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bell-notification-square-fill" {...props}></Icon>
