<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zalphcmjo.css';
import '../../css/f/fqa96gb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zalphcmjo"/><path class="fqa96gb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:button-flush-left" {...props}></Icon>
