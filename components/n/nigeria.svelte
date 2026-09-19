<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htkm44bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htkm44bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nigeria" {...props}></Icon>
