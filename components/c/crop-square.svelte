<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ienf_jm6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ienf_jm6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crop-square" {...props}></Icon>
