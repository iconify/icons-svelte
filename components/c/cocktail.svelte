<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it526ibql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="it526ibql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cocktail" {...props}></Icon>
