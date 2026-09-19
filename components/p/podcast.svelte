<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf33wdima.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rf33wdima"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:podcast" {...props}></Icon>
