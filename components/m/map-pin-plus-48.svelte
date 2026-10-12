<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1brf6mxa.css';
import '../../css/x/xou2jbzza.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s1brf6mxa"/><path class="xou2jbzza"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-plus-48" {...props}></Icon>
