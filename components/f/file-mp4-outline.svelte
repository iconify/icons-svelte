<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reqybcxbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="reqybcxbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-mp4-outline" {...props}></Icon>
