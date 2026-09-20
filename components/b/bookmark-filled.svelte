<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agl78fbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="agl78fbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:bookmark-filled" {...props}></Icon>
