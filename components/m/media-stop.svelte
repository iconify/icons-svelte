<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2so9dl7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="p2so9dl7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:media-stop" {...props}></Icon>
