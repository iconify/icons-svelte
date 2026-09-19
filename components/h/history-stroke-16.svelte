<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw4bg-oew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vw4bg-oew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:history-stroke-16" {...props}></Icon>
