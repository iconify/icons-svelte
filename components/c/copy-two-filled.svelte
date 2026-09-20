<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkav4jb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zkav4jb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:copy-two-filled" {...props}></Icon>
