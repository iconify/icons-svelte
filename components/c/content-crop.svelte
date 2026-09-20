<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4-dr1gfb.css';
import '../../css/q/qql1b-83c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x4-dr1gfb"/><path class="qql1b-83c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-crop" {...props}></Icon>
