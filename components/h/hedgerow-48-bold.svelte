<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y83ielkqr.css';
import '../../css/y/y-605nsjq.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y83ielkqr"/><path class="y-605nsjq"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hedgerow-48-bold" {...props}></Icon>
