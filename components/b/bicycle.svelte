<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym7s1o7nd.css';
import '../../css/c/cgzpch7-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ym7s1o7nd"/><path class="cgzpch7-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bicycle" {...props}></Icon>
