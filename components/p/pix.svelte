<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoibcycal.css';
import '../../css/r/rewt-b9oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yoibcycal"/><path class="rewt-b9oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:pix" {...props}></Icon>
