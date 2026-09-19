<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gine0sb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gine0sb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heavy-helm" {...props}></Icon>
