<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwzq31xlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwzq31xlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-esp" {...props}></Icon>
