<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvjyayb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvjyayb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-pulse-solid" {...props}></Icon>
