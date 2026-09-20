<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l46mue4pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l46mue4pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-2-fill" {...props}></Icon>
