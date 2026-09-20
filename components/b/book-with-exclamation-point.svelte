<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m__zv7bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m__zv7bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-exclamation-point" {...props}></Icon>
