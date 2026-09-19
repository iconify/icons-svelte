<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6v5fxbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y6v5fxbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:image" {...props}></Icon>
