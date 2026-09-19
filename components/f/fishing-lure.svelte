<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa4e-v7zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wa4e-v7zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fishing-lure" {...props}></Icon>
