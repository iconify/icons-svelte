<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k83m2lbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k83m2lbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:l" {...props}></Icon>
