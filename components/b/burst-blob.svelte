<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq34o7myt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fq34o7myt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:burst-blob" {...props}></Icon>
