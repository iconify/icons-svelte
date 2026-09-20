<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obyc-wpuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="obyc-wpuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-alert-alarm-bell-2-alert-bell-ring-notification-alarm" {...props}></Icon>
