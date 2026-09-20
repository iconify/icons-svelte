<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3i5_5bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w3i5_5bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:join-corner-arrow-3" {...props}></Icon>
