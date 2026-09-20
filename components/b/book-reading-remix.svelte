<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hudq7c7gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hudq7c7gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:book-reading-remix" {...props}></Icon>
