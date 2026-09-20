<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3i8yv6ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3i8yv6ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-pause" {...props}></Icon>
