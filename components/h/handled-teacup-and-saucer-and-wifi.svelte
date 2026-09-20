<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt86abese.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bt86abese"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:handled-teacup-and-saucer-and-wifi" {...props}></Icon>
