<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukp4s0b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ukp4s0b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:j-outline" {...props}></Icon>
