<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlsc79brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rlsc79brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-stop-remix" {...props}></Icon>
