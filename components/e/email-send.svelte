<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvyhlw8lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvyhlw8lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-send" {...props}></Icon>
