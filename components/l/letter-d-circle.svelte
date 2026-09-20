<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrmumqbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrmumqbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-d-circle" {...props}></Icon>
