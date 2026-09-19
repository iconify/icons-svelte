<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_6-igbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n_6-igbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plant-watering" {...props}></Icon>
