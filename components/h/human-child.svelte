<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msh6ovb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msh6ovb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-child" {...props}></Icon>
