<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz9uo7bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz9uo7bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boom-arm-down-outline" {...props}></Icon>
