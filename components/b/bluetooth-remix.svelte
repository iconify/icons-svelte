<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruy4n5q6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ruy4n5q6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bluetooth-remix" {...props}></Icon>
