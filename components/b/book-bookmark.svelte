<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4iyfj41i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e4iyfj41i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:book-bookmark" {...props}></Icon>
