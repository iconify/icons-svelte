<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4r5-ok7c.css';
import '../../css/a/an49idj0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n4r5-ok7c"/><path class="an49idj0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:log-out" {...props}></Icon>
