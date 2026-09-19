<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb7q07bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cb7q07bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:calendar" {...props}></Icon>
