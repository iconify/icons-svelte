<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npskko2ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npskko2ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lufthansa" {...props}></Icon>
