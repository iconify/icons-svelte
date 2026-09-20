<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3_cyn3bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i3_cyn3bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nebraska-with-capital-star" {...props}></Icon>
