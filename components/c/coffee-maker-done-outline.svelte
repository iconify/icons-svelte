<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu2cbnbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu2cbnbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coffee-maker-done-outline" {...props}></Icon>
