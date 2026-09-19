<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzgn6nyji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pzgn6nyji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hot-surface" {...props}></Icon>
