<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwdn4qbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwdn4qbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fruit-cherries-off" {...props}></Icon>
