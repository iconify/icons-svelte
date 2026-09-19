<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp29a1_7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wp29a1_7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:head-side-bold" {...props}></Icon>
