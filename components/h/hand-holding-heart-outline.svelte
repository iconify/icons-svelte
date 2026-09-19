<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk7d680ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pk7d680ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding-heart-outline" {...props}></Icon>
