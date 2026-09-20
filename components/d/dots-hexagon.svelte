<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz4fvdbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz4fvdbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dots-hexagon" {...props}></Icon>
