<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj6pdebvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qj6pdebvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-movie-outline" {...props}></Icon>
