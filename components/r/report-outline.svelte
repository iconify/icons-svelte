<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k88a7yboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k88a7yboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:report-outline" {...props}></Icon>
