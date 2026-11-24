<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqizw4bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqizw4bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:handshake" {...props}></Icon>
