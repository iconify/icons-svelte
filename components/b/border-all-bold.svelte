<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf0779bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hf0779bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-all-bold" {...props}></Icon>
