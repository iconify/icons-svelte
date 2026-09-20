<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bscwe4z-x.css';
import '../../css/i/iuqenpiuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bscwe4z-x"/><path class="iuqenpiuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:internet-network-wifi-monitor" {...props}></Icon>
