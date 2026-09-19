<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppkhjhbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ppkhjhbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fire-duo" {...props}></Icon>
