<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgsi0rb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgsi0rb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:aperture" {...props}></Icon>
