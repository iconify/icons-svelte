<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1mzqkyge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z1mzqkyge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-key" {...props}></Icon>
