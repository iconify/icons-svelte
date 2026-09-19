<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5z1rjb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i5z1rjb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:phone-outline" {...props}></Icon>
