<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgc8t-bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgc8t-bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:games-outline" {...props}></Icon>
