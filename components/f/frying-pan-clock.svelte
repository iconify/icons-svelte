<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-cto4hid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-cto4hid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:frying-pan-clock" {...props}></Icon>
