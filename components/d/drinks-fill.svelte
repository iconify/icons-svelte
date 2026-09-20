<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nefux0p3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nefux0p3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drinks-fill" {...props}></Icon>
