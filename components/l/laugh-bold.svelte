<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swybqzb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="swybqzb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:laugh-bold" {...props}></Icon>
