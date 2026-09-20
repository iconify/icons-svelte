<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfc8sf6fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfc8sf6fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:poker-heart" {...props}></Icon>
