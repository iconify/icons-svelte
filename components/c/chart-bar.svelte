<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy12u3bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="sy12u3bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-bar" {...props}></Icon>
