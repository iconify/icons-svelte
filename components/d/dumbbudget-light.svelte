<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anwk4fogy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anwk4fogy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbbudget-light" {...props}></Icon>
