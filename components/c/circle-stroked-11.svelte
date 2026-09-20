<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldqzoubhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ldqzoubhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:circle-stroked-11" {...props}></Icon>
