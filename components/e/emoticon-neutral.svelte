<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyooy8g6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyooy8g6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-neutral" {...props}></Icon>
