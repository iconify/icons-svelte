<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6cd9uo2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="b6cd9uo2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mallet-outline" {...props}></Icon>
