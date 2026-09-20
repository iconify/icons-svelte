<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vviwdlbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vviwdlbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:label-solid" {...props}></Icon>
