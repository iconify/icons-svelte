<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fex8azbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fex8azbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:curvy-left-direction" {...props}></Icon>
