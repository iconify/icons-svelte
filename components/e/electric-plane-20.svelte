<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u75ne53rx.css';
import '../../css/q/q0cgw-bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u75ne53rx"/><path class="q0cgw-bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-plane-20" {...props}></Icon>
