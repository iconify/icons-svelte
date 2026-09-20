<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2inalyzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w2inalyzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:pulse" {...props}></Icon>
