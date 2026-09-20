<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l30pv5y8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l30pv5y8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:join-corner-arrow-4" {...props}></Icon>
