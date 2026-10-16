<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndt99pbau.css';
import '../../css/x/x908mum4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ndt99pbau"/><path class="x908mum4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:current-transformer-48-bold" {...props}></Icon>
