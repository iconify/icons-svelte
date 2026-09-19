<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_rjcdbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":90,"height":80};
const content = `<path clip-rule="evenodd" class="j_rjcdbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cogs-1-bold" {...props}></Icon>
