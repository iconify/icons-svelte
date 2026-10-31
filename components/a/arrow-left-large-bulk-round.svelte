<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnfar-bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnfar-bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-large-bulk-round" {...props}></Icon>
