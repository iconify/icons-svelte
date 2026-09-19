<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_xuckbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="k_xuckbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloudupload" {...props}></Icon>
