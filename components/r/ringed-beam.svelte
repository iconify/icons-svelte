<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr7k__z1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zr7k__z1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ringed-beam" {...props}></Icon>
