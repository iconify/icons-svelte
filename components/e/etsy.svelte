<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_6lzl0ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="u_6lzl0ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:etsy" {...props}></Icon>
