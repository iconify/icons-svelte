<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiuj1-afm.css';
import '../../css/w/wd15b2bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yiuj1-afm"/><path clip-rule="evenodd" class="wd15b2bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:right-square-filled" {...props}></Icon>
