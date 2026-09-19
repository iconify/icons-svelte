<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns-s0jb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ns-s0jb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:full-metal-bucket-handle" {...props}></Icon>
