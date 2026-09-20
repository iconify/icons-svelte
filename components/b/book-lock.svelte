<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i680wacod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i680wacod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-lock" {...props}></Icon>
