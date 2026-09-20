<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wch7bzvmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wch7bzvmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-help-outline" {...props}></Icon>
