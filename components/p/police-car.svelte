<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfrm7eblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfrm7eblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:police-car" {...props}></Icon>
