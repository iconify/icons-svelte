<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvxo8ft8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kvxo8ft8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:heavy-rain-outline" {...props}></Icon>
