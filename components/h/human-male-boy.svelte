<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccir8bbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccir8bbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-male-boy" {...props}></Icon>
