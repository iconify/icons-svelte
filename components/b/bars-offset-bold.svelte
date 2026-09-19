<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyw-t95-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qyw-t95-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset-bold" {...props}></Icon>
