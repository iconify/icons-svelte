<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1y_cbcio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w1y_cbcio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:closed-captioning-slash" {...props}></Icon>
