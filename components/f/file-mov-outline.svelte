<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxpizu1yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bxpizu1yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-mov-outline" {...props}></Icon>
