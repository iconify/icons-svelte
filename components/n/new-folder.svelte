<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0tui7bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p0tui7bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:new-folder" {...props}></Icon>
