<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d94pbcbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d94pbcbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:grid-1x2-fill" {...props}></Icon>
