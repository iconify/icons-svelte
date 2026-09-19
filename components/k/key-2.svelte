<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkjklj6ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="bkjklj6ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:key-2" {...props}></Icon>
