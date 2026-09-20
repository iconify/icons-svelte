<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drz4_tb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drz4_tb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-outline" {...props}></Icon>
