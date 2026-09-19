<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3a_arbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h3a_arbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crosshairs-1-outline" {...props}></Icon>
