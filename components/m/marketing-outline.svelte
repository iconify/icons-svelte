<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvy6d57rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xvy6d57rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:marketing-outline" {...props}></Icon>
