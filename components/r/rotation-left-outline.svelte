<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coai96h7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="coai96h7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rotation-left-outline" {...props}></Icon>
