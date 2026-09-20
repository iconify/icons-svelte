<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gettf3w-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gettf3w-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pick-hammer-with-rocks" {...props}></Icon>
