<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt31c58xs.css';
import '../../css/l/lwvq-ccsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yt31c58xs"/><path class="lwvq-ccsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netbird" {...props}></Icon>
