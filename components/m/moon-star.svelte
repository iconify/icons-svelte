<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrb7py0ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrb7py0ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:moon-star" {...props}></Icon>
