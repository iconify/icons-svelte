<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt3masb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yt3masb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:geo-location-24px" {...props}></Icon>
