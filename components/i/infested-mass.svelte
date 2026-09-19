<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxm9r3d5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxm9r3d5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:infested-mass" {...props}></Icon>
