<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cakwvye_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cakwvye_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-plus" {...props}></Icon>
