<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klk_9ybhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klk_9ybhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-letter-case-upper" {...props}></Icon>
