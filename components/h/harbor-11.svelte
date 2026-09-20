<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seiiy8a5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="seiiy8a5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:harbor-11" {...props}></Icon>
