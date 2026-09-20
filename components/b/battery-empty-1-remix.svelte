<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d95zj-bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d95zj-bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-empty-1-remix" {...props}></Icon>
