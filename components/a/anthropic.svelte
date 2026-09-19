<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lexjn9bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lexjn9bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:anthropic" {...props}></Icon>
