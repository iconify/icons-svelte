<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifsc1nbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ifsc1nbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:propane-tank-with-recycling-symbol" {...props}></Icon>
