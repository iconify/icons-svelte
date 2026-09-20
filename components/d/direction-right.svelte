<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdi9gst5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdi9gst5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:direction-right" {...props}></Icon>
