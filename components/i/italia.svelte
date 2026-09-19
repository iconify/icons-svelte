<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-jl-jb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h-jl-jb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:italia" {...props}></Icon>
