<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo5q_abex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo5q_abex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:car-parking-01" {...props}></Icon>
