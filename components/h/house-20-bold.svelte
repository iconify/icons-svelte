<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coivkzecr.css';
import '../../css/b/batf86bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="batf86bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-20-bold" {...props}></Icon>
