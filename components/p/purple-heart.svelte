<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2jwnnbyn.css';
import '../../css/t/tqz5znvkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g2jwnnbyn"/><path class="tqz5znvkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:purple-heart" {...props}></Icon>
