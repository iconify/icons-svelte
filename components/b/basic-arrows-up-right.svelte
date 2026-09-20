<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-gecly6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-gecly6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-up-right" {...props}></Icon>
