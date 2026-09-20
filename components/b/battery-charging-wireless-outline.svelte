<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8f6byc7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8f6byc7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-wireless-outline" {...props}></Icon>
