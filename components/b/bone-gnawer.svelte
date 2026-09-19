<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ddp93cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-ddp93cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bone-gnawer" {...props}></Icon>
