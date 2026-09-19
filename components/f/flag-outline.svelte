<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikov2ccdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ikov2ccdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:flag-outline" {...props}></Icon>
