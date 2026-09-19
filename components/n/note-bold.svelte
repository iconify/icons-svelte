<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1zgeubyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="x1zgeubyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-bold" {...props}></Icon>
