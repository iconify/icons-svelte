<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj9hlqbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pj9hlqbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:banknote-in-slot" {...props}></Icon>
