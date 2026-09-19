<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5ma-1b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x5ma-1b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:currency-rupee" {...props}></Icon>
