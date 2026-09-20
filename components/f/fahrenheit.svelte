<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8nuilbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="j8nuilbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:fahrenheit" {...props}></Icon>
