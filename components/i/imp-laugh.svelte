<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpf6b1bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpf6b1bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:imp-laugh" {...props}></Icon>
