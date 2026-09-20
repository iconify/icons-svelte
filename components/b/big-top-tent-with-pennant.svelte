<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r401p9bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r401p9bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:big-top-tent-with-pennant" {...props}></Icon>
