<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6y3f0b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g6y3f0b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chevron-left" {...props}></Icon>
