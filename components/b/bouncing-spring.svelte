<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prx_0ebow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prx_0ebow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bouncing-spring" {...props}></Icon>
