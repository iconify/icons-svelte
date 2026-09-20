<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk1ibeynv.css';
import '../../css/y/yettion4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nk1ibeynv"/><path class="yettion4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-wi-fi" {...props}></Icon>
