<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo8l09wir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wo8l09wir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ear-duo" {...props}></Icon>
