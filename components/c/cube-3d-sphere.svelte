<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irqascczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irqascczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cube-3d-sphere" {...props}></Icon>
