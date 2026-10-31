<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuvy8ubpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuvy8ubpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clover-bulk-round" {...props}></Icon>
