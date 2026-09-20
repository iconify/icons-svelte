<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4psys0ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j4psys0ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dollar" {...props}></Icon>
