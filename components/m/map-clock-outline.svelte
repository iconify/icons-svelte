<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp1w73bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp1w73bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-clock-outline" {...props}></Icon>
