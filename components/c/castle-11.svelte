<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn3et2b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="yn3et2b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:castle-11" {...props}></Icon>
