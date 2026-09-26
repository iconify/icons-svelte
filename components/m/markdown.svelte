<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twl58k00n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="twl58k00n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:markdown" {...props}></Icon>
