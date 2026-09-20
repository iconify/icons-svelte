<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7kfs-bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i7kfs-bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:music-outline" {...props}></Icon>
