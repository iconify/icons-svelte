<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rezryb9cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rezryb9cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-share" {...props}></Icon>
