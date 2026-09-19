<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-5itzcvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-5itzcvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:moai" {...props}></Icon>
