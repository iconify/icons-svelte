<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kobzaq9ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kobzaq9ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-ring-fill-round" {...props}></Icon>
