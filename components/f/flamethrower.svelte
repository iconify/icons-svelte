<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csh7irwwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="csh7irwwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flamethrower" {...props}></Icon>
