<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei1baibta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1baibta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-off" {...props}></Icon>
