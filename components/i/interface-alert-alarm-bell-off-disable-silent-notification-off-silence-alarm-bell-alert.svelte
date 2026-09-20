<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p30qmac3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p30qmac3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-alert-alarm-bell-off-disable-silent-notification-off-silence-alarm-bell-alert" {...props}></Icon>
