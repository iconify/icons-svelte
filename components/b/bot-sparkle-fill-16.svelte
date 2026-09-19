<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa7mqbxdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sa7mqbxdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bot-sparkle-fill-16" {...props}></Icon>
