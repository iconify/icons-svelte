<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_fx5cbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_fx5cbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-triple-down" {...props}></Icon>
