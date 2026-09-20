<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z21hg6baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z21hg6baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:offline" {...props}></Icon>
