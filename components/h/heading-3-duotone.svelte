<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_xy-hb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_xy-hb0a primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heading-3-duotone" {...props}></Icon>
