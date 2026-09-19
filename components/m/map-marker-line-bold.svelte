<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwfoiyz9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nwfoiyz9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:map-marker-line-bold" {...props}></Icon>
