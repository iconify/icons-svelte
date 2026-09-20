<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kob1615rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kob1615rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openlist-light" {...props}></Icon>
