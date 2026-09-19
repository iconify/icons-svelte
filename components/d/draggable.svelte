<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktjlns3zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ktjlns3zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:draggable" {...props}></Icon>
