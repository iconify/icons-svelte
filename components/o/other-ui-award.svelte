<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo5-5tayx.css';
import '../../css/a/ars70-b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vo5-5tayx"/><path clip-rule="evenodd" class="ars70-b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-award" {...props}></Icon>
