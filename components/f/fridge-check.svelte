<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wly1u2umf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wly1u2umf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fridge-check" {...props}></Icon>
