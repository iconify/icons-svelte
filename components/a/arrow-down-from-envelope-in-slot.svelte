<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb9a57b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wb9a57b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-from-envelope-in-slot" {...props}></Icon>
