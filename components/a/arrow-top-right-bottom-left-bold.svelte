<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm1lafg_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1lafg_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-right-bottom-left-bold" {...props}></Icon>
