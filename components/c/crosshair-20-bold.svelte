<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nain0n-0j.css';
import '../../css/z/zr6oosbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nain0n-0j"/><path class="zr6oosbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crosshair-20-bold" {...props}></Icon>
