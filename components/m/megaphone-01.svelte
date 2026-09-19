<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq0gxh6nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq0gxh6nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:megaphone-01" {...props}></Icon>
