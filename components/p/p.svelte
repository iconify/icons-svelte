<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n38uvsbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="n38uvsbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:p" {...props}></Icon>
