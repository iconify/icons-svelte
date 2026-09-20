<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s52z4mbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s52z4mbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-down-right" {...props}></Icon>
