<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg85dnbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg85dnbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:data-matrix-scan" {...props}></Icon>
