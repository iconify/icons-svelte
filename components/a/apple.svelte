<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-qf5gbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="h-qf5gbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:apple" {...props}></Icon>
