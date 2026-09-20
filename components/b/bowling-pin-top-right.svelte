<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e97trkb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e97trkb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bowling-pin-top-right" {...props}></Icon>
