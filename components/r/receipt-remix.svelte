<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f77-4yb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f77-4yb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:receipt-remix" {...props}></Icon>
