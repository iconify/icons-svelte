<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb-1labtg.css';
import '../../css/h/hfcvhcccg.css';
import '../../css/y/yiybycb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="wb-1labtg"/><path class="hfcvhcccg"/><path class="yiybycb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:host-solid-alerted" {...props}></Icon>
