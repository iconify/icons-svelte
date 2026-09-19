<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtevctbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jtevctbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:join-inner-alt" {...props}></Icon>
