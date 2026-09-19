<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f65yucmlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="f65yucmlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:handshake-slash" {...props}></Icon>
