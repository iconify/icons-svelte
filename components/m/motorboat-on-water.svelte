<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqlmd9qxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zqlmd9qxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-on-water" {...props}></Icon>
