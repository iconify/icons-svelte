<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmwchobpn.css';
import '../../css/e/e8_03wb-a.css';
import '../../css/a/av5-hcwri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="vmwchobpn"/><path class="e8_03wb-a"/><path class="av5-hcwri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:drop-of-blood" {...props}></Icon>
