<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snx1k3x0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snx1k3x0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:deer-head" {...props}></Icon>
