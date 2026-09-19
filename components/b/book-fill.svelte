<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7nap4bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q7nap4bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:book-fill" {...props}></Icon>
