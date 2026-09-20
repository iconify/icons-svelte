<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc4b3b0tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pc4b3b0tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:calendar" {...props}></Icon>
