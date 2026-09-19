<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdr3yo2xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zdr3yo2xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:plug" {...props}></Icon>
