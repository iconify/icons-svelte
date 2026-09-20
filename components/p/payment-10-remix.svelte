<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryn-zw0rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ryn-zw0rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:payment-10-remix" {...props}></Icon>
