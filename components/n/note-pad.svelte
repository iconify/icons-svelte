<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frsy2rb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="frsy2rb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-pad" {...props}></Icon>
