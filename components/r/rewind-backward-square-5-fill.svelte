<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxufovavu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxufovavu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-5-fill" {...props}></Icon>
