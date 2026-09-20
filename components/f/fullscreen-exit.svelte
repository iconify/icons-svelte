<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kob3cc21s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kob3cc21s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fullscreen-exit" {...props}></Icon>
