<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv5yvyzmk.css';
import '../../css/y/y6o6t-piu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tv5yvyzmk"/><path class="y6o6t-piu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ethernet-port-20" {...props}></Icon>
