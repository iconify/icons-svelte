<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxdi6zbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lxdi6zbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-pad-bold" {...props}></Icon>
