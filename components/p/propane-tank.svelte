<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu2hdnbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu2hdnbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:propane-tank" {...props}></Icon>
