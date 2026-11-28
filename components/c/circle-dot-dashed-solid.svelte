<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtm5gdvwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtm5gdvwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-dot-dashed-solid" {...props}></Icon>
