<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1o_6mbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a1o_6mbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:back-pain" {...props}></Icon>
