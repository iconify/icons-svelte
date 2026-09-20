<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu9nlz-2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nu9nlz-2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pole-with-floodlights" {...props}></Icon>
