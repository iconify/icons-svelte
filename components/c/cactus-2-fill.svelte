<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st6p60b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st6p60b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cactus-2-fill" {...props}></Icon>
