<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm4b4se3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm4b4se3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-check-filled" {...props}></Icon>
