<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l14ulwbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="l14ulwbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-exchange" {...props}></Icon>
