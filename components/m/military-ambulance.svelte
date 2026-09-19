<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id1l07j3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="id1l07j3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:military-ambulance" {...props}></Icon>
