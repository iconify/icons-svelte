<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnwtjmb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fnwtjmb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-from-ticket-in-slot" {...props}></Icon>
