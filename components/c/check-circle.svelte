<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-8l21bot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-8l21bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:check-circle" {...props}></Icon>
