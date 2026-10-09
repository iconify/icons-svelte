<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7plo0j7z.css';
import '../../css/c/crwtq5bps.css';
import '../../css/i/ijtbhzpet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w7plo0j7z"/><path class="crwtq5bps"/><path class="ijtbhzpet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sync-48-bold" {...props}></Icon>
