<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkr2q8ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkr2q8ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alarmpi-light" {...props}></Icon>
