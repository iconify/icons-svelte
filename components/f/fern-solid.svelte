<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmp5x_b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmp5x_b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fern-solid" {...props}></Icon>
