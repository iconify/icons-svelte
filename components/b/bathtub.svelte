<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxff9dbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxff9dbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bathtub" {...props}></Icon>
