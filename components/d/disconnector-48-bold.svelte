<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uww01kbpv.css';
import '../../css/i/ifa5gsbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uww01kbpv"/><path class="ifa5gsbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:disconnector-48-bold" {...props}></Icon>
