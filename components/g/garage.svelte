<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id-dlnwlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="id-dlnwlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:garage" {...props}></Icon>
