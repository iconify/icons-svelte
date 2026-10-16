<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kob1hjbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kob1hjbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-spill-48" {...props}></Icon>
