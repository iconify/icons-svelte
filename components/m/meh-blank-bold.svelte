<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j02izstjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="j02izstjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:meh-blank-bold" {...props}></Icon>
