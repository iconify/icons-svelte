<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3oe6jemu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t3oe6jemu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-line-end" {...props}></Icon>
