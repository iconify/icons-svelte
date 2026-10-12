<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw62wh_1x.css';
import '../../css/p/poade0yht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gw62wh_1x"/><path class="poade0yht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dock-filled" {...props}></Icon>
