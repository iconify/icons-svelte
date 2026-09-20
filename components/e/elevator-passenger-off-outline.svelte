<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aic86hbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aic86hbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elevator-passenger-off-outline" {...props}></Icon>
