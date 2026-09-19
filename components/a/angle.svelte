<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_n7hgyks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="i_n7hgyks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:angle" {...props}></Icon>
