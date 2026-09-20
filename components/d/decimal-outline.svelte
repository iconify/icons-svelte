<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo3u2n3vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zo3u2n3vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:decimal-outline" {...props}></Icon>
