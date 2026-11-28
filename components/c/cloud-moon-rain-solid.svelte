<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjok1613k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjok1613k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-moon-rain-solid" {...props}></Icon>
