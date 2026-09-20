<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fce5mu9wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fce5mu9wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:link-outline" {...props}></Icon>
