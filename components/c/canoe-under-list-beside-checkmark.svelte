<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg1ear06l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yg1ear06l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-under-list-beside-checkmark" {...props}></Icon>
