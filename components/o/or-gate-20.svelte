<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gza0lnxru.css';
import '../../css/l/lcdh-cbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gza0lnxru"/><path class="lcdh-cbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:or-gate-20" {...props}></Icon>
