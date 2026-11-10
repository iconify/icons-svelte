<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i73l00gnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i73l00gnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:noodle-bowl" {...props}></Icon>
