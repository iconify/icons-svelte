<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di2q-x_mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="di2q-x_mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:angle-double-bold" {...props}></Icon>
