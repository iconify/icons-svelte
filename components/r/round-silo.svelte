<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9cnvh3qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9cnvh3qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:round-silo" {...props}></Icon>
