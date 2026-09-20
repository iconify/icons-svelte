<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_cyk1bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_cyk1bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fried-potatoes" {...props}></Icon>
