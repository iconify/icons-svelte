<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t544ezb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t544ezb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:k-bold" {...props}></Icon>
