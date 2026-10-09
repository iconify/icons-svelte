<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgrtu-b6i.css';
import '../../css/l/ldszce0qy.css';
import '../../css/q/q5jodccjc.css';
import '../../css/h/huyo77usb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgrtu-b6i"/><path class="ldszce0qy"/><path class="q5jodccjc"/><path class="huyo77usb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:community-energy-48" {...props}></Icon>
