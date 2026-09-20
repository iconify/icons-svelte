<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2ar__b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v2ar__b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lattice-tower-with-ball-tip-antenna-on-ground-with-beams" {...props}></Icon>
