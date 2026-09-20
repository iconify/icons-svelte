<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmebte2ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmebte2ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-brush-outline" {...props}></Icon>
