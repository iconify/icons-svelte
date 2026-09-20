<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r80c0vbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r80c0vbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reboot" {...props}></Icon>
