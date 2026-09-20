<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt6g47bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt6g47bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-outline" {...props}></Icon>
