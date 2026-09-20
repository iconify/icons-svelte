<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzw0mk9ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rzw0mk9ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:incoming-call" {...props}></Icon>
