<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/horf_2btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="horf_2btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:grain" {...props}></Icon>
