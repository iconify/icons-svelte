<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0r-2hb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j0r-2hb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:champagne-party-alcohol-remix" {...props}></Icon>
