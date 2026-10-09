<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8bmplu8s.css';
import '../../css/v/vgb2cgbyg.css';
import '../../css/k/kiw8kob5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l8bmplu8s"/><path class="vgb2cgbyg"/><path class="kiw8kob5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:headset-20-bold" {...props}></Icon>
