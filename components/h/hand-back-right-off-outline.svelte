<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viert1r8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="viert1r8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-back-right-off-outline" {...props}></Icon>
