<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smi51_bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smi51_bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pulley-hook" {...props}></Icon>
