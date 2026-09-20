<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4998ztny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d4998ztny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:heart" {...props}></Icon>
