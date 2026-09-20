<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8wwcmd7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8wwcmd7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:left-up-corner-arrow-1" {...props}></Icon>
