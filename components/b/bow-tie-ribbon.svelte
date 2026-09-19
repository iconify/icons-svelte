<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj7o5x-om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rj7o5x-om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bow-tie-ribbon" {...props}></Icon>
