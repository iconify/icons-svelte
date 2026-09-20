<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prxccrbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="prxccrbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bookmark-outline" {...props}></Icon>
