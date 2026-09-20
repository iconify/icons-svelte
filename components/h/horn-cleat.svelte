<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8yw98b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j8yw98b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horn-cleat" {...props}></Icon>
