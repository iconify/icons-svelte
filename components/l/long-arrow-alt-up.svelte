<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j29yx1bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j29yx1bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:long-arrow-alt-up" {...props}></Icon>
