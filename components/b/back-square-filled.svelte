<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cakywobim.css';
import '../../css/i/iz024ebeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cakywobim"/><path clip-rule="evenodd" class="iz024ebeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:back-square-filled" {...props}></Icon>
