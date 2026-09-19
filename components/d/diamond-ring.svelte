<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h50f4zr4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h50f4zr4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:diamond-ring" {...props}></Icon>
