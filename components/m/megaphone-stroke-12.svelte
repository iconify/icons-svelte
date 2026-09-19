<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3-abubmf.css';
import '../../css/j/j9m0dh2uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y3-abubmf"/><path class="j9m0dh2uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:megaphone-stroke-12" {...props}></Icon>
