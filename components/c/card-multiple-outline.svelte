<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s16uusb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s16uusb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-multiple-outline" {...props}></Icon>
