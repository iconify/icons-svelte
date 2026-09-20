<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr0mjqbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr0mjqbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:antenna-off" {...props}></Icon>
