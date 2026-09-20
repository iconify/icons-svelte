<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4og4digd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y4og4digd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-blur-remix" {...props}></Icon>
