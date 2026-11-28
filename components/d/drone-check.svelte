<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzi68vx8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzi68vx8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:drone-check" {...props}></Icon>
