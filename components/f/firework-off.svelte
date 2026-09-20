<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_u8rob9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_u8rob9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:firework-off" {...props}></Icon>
