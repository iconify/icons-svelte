<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_drazbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_drazbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ice-cream" {...props}></Icon>
