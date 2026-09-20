<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pimcu1bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pimcu1bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:maine-with-capital-star" {...props}></Icon>
