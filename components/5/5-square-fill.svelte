<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlrybwbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dlrybwbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:5-square-fill" {...props}></Icon>
