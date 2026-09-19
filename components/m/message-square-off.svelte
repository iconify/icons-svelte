<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw9kfbbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw9kfbbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square-off" {...props}></Icon>
