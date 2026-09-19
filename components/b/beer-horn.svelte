<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjee6g_jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qjee6g_jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beer-horn" {...props}></Icon>
