<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm--x3eex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bm--x3eex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:presentation" {...props}></Icon>
