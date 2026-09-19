<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4_w-d8ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f4_w-d8ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:app-connectivity" {...props}></Icon>
