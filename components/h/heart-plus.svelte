<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7hz3j1pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7hz3j1pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-plus" {...props}></Icon>
