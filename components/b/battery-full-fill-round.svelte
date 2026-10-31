<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpvss8lpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpvss8lpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-full-fill-round" {...props}></Icon>
