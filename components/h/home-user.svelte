<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3c4xk9ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q3c4xk9ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:home-user" {...props}></Icon>
