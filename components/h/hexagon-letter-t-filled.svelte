<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1_9y1rgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1_9y1rgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-t-filled" {...props}></Icon>
