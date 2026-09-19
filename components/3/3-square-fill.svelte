<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwl79gqjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rwl79gqjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:3-square-fill" {...props}></Icon>
