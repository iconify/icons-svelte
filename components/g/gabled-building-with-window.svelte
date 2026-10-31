<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe9q90bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xe9q90bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-building-with-window" {...props}></Icon>
