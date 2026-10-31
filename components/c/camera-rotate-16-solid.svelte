<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxcq6swps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uxcq6swps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:camera-rotate-16-solid" {...props}></Icon>
