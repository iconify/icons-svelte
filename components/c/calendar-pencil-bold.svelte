<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6dt8aclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p6dt8aclf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-pencil-bold" {...props}></Icon>
