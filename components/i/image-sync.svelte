<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_44i-vgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_44i-vgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-sync" {...props}></Icon>
