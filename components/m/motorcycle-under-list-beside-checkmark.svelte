<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr4t8iznt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vr4t8iznt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-under-list-beside-checkmark" {...props}></Icon>
