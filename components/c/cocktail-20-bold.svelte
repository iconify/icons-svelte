<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7zm0u_6f.css';
import '../../css/j/jiqi-hb6a.css';
import '../../css/x/xf-_f2-0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m7zm0u_6f"/><path class="jiqi-hb6a"/><path class="xf-_f2-0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cocktail-20-bold" {...props}></Icon>
