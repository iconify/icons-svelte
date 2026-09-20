<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1qs6fb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h1qs6fb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dollar-swap-to-euro" {...props}></Icon>
