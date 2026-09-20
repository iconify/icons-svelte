<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyw49evoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jyw49evoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lantern-lamppost" {...props}></Icon>
