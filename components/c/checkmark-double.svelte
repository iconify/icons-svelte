<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_essbbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b_essbbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkmark-double" {...props}></Icon>
