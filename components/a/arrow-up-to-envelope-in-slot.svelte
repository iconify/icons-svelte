<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t37u2kbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t37u2kbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-envelope-in-slot" {...props}></Icon>
