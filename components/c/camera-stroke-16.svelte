<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud1m1c5-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ud1m1c5-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:camera-stroke-16" {...props}></Icon>
