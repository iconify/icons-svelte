<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2m0k31jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s2m0k31jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:full-width-stroke-16" {...props}></Icon>
