<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht2xmabmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ht2xmabmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lips" {...props}></Icon>
