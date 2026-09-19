<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aplqkl7uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="aplqkl7uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-center-duo" {...props}></Icon>
