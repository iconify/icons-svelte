<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbzico_az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbzico_az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-poop-outline" {...props}></Icon>
