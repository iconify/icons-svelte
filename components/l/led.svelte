<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr35tybjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dr35tybjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:led" {...props}></Icon>
