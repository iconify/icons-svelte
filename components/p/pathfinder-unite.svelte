<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw-jlrbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw-jlrbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pathfinder-unite" {...props}></Icon>
