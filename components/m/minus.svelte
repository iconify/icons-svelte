<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc7yqi9bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="dc7yqi9bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:minus" {...props}></Icon>
