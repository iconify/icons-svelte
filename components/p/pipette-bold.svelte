<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hko-q4lad.css';
import '../../css/u/ujph6vdwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hko-q4lad"/><path class="ujph6vdwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pipette-bold" {...props}></Icon>
