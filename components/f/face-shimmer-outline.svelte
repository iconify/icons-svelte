<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfwkjt-vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfwkjt-vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-shimmer-outline" {...props}></Icon>
