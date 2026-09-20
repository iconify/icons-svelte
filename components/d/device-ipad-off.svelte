<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hra2rzbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hra2rzbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-off" {...props}></Icon>
