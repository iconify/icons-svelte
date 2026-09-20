<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr0ffdc1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yr0ffdc1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:fire-outline" {...props}></Icon>
