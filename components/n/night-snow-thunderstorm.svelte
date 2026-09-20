<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx5a0xb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="tx5a0xb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-snow-thunderstorm" {...props}></Icon>
