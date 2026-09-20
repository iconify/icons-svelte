<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3suvebfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a3suvebfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:drink-bottle-and-milk-carton-and-can" {...props}></Icon>
