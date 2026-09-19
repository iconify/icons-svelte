<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti120ucnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ti120ucnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-2" {...props}></Icon>
