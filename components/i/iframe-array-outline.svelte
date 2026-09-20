<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzn2au2sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzn2au2sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iframe-array-outline" {...props}></Icon>
