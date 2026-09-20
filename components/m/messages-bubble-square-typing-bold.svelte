<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvkcdmb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvkcdmb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:messages-bubble-square-typing-bold" {...props}></Icon>
