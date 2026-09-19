<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy8lgtbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gy8lgtbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-none" {...props}></Icon>
