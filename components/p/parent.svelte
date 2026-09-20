<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnquiab7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rnquiab7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:parent" {...props}></Icon>
