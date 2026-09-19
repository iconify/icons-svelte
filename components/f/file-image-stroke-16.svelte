<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idzt2o2kr.css';
import '../../css/p/pmqt2cblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="idzt2o2kr"/><circle class="pmqt2cblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-image-stroke-16" {...props}></Icon>
