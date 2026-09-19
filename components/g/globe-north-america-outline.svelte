<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2-pfdccx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z2-pfdccx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-north-america-outline" {...props}></Icon>
