<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q93rtebqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="q93rtebqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fire" {...props}></Icon>
