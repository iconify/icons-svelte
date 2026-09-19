<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzew16btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vzew16btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heading" {...props}></Icon>
