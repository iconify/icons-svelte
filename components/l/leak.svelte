<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-0_eb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jt-0_eb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:leak" {...props}></Icon>
