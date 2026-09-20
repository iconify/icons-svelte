<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkff7l4ev.css';
import '../../css/s/stwvedcof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rkff7l4ev"/><path class="stwvedcof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:internet-network-computer-upload" {...props}></Icon>
