<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh064mfkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zh064mfkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-exclamation-2" {...props}></Icon>
