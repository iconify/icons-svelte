<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-uydrm2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-uydrm2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:robber-hand" {...props}></Icon>
