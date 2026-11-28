<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxf9zc3us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxf9zc3us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:car-off-solid" {...props}></Icon>
