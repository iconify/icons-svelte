<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_y22ybks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="j_y22ybks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:finance" {...props}></Icon>
