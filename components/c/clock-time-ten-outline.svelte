<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtg7zvgcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtg7zvgcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-ten-outline" {...props}></Icon>
