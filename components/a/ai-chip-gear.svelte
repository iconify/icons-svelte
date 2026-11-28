<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgndzlwyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgndzlwyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ai-chip-gear" {...props}></Icon>
