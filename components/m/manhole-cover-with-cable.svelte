<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkehd8ptn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pkehd8ptn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:manhole-cover-with-cable" {...props}></Icon>
