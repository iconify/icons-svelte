<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z735ileap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z735ileap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mac-10" {...props}></Icon>
