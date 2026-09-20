<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0htzcbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w0htzcbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:inventory-outline" {...props}></Icon>
