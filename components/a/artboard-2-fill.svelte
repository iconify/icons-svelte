<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3azj_gbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3azj_gbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:artboard-2-fill" {...props}></Icon>
