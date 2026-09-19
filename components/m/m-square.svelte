<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p32b85x_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="p32b85x_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:m-square" {...props}></Icon>
