<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn1pn-dlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bn1pn-dlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circle-outline-with-top-left-quarter-and-bottom-right-quarter" {...props}></Icon>
