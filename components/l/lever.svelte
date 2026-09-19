<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4r5_k7pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4r5_k7pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lever" {...props}></Icon>
