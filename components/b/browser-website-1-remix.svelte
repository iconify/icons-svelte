<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7s8iu7on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x7s8iu7on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-website-1-remix" {...props}></Icon>
