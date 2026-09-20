<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggbltf6qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggbltf6qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:avalanche" {...props}></Icon>
