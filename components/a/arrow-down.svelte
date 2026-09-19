<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebldvkbho.css';
import '../../css/a/auxk0ec3j.css';
import '../../css/r/rpsvq3bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="auxk0ec3j"/><path class="rpsvq3bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:arrow-down" {...props}></Icon>
