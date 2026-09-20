<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksa7z7pcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksa7z7pcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-off" {...props}></Icon>
