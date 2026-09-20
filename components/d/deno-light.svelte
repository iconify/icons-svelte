<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh9lg8b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":401,"height":401};
const content = `<path class="bh9lg8b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deno-light" {...props}></Icon>
