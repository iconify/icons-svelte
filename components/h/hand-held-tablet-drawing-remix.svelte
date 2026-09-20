<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpw9e4bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lpw9e4bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-held-tablet-drawing-remix" {...props}></Icon>
