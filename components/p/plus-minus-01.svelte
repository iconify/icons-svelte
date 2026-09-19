<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwa1c4o_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwa1c4o_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:plus-minus-01" {...props}></Icon>
