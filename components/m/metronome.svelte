<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvgt0nbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvgt0nbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:metronome" {...props}></Icon>
