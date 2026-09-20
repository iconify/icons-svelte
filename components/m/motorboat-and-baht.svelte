<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jew7w5bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jew7w5bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-baht" {...props}></Icon>
