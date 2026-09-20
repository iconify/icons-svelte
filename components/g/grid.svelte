<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvrky_bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yvrky_bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:grid" {...props}></Icon>
