<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxnm8cc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gxnm8cc6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crosshair-arrow" {...props}></Icon>
