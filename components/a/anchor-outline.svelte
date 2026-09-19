<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxp6_5wni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fxp6_5wni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:anchor-outline" {...props}></Icon>
