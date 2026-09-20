<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s19nmm6ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s19nmm6ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mobile-phone-off" {...props}></Icon>
