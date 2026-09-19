<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4sdsnbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a4sdsnbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-gg" {...props}></Icon>
