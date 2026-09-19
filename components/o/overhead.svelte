<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvbrnhbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvbrnhbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:overhead" {...props}></Icon>
