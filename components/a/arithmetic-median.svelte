<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_dy700on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q_dy700on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arithmetic-median" {...props}></Icon>
