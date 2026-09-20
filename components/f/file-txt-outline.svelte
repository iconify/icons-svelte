<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn5q14rop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nn5q14rop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-txt-outline" {...props}></Icon>
