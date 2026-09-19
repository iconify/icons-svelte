<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwy-ycizl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nwy-ycizl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:opt" {...props}></Icon>
