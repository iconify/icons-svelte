<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv0yjqb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zv0yjqb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-ee" {...props}></Icon>
