<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayh0pmhui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayh0pmhui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pin-off-round" {...props}></Icon>
