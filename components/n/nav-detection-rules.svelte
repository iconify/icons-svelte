<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0tz_5blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d0tz_5blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-detection-rules" {...props}></Icon>
