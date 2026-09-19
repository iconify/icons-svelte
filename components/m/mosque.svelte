<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0l4rc-vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="v0l4rc-vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mosque" {...props}></Icon>
