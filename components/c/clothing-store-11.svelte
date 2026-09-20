<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl_kitb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="pl_kitb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:clothing-store-11" {...props}></Icon>
