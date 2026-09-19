<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtk-o_b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtk-o_b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pacman" {...props}></Icon>
