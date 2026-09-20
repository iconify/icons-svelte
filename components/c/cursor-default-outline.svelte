<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb0fx9bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb0fx9bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cursor-default-outline" {...props}></Icon>
