<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th5jkqp1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="th5jkqp1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:in-columns" {...props}></Icon>
