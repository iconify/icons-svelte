<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bad0-bbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bad0-bbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:full-screen-exit" {...props}></Icon>
