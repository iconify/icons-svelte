<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4oi2s2oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="v4oi2s2oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-right-bold" {...props}></Icon>
