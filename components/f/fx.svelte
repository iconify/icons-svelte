<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj_bjqbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj_bjqbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fx" {...props}></Icon>
