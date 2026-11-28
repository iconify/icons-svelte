<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuoeadbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuoeadbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:robot-vacuum-pause" {...props}></Icon>
