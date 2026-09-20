<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icb3i3bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icb3i3bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-circle" {...props}></Icon>
