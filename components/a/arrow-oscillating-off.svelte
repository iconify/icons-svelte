<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co0ju6ars.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co0ju6ars"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-oscillating-off" {...props}></Icon>
