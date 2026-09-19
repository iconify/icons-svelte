<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3hh6zbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a3hh6zbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:link-duo" {...props}></Icon>
