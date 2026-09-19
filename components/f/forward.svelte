<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n93xk4ohs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n93xk4ohs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:forward" {...props}></Icon>
