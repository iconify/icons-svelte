<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em3hccbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="em3hccbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:music-note" {...props}></Icon>
