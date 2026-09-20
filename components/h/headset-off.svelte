<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-uch-rpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-uch-rpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:headset-off" {...props}></Icon>
