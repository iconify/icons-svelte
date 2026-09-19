<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxy3m40ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="kxy3m40ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cursor-outline" {...props}></Icon>
