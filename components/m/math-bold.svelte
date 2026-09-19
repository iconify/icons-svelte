<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_8et7y8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g_8et7y8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:math-bold" {...props}></Icon>
