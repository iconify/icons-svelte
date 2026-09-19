<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohbqhs6vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ohbqhs6vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:p" {...props}></Icon>
