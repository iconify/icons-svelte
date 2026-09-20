<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3k_j8bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e3k_j8bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray-and-euro" {...props}></Icon>
