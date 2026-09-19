<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da27hnbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="da27hnbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fire-1-bold" {...props}></Icon>
