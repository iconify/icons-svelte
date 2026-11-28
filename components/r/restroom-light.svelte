<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9xf69qzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o9xf69qzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:restroom-light" {...props}></Icon>
