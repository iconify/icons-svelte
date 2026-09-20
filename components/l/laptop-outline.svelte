<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1p2xto-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j1p2xto-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:laptop-outline" {...props}></Icon>
