<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy4q2qsdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6,"height":16};
const content = `<path class="wy4q2qsdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-small-up" {...props}></Icon>
