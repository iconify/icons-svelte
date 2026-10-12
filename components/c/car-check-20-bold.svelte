<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9032gb0e.css';
import '../../css/y/yw5vbabhn.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f9032gb0e"/><path class="yw5vbabhn"/><path class="aqsnv9bnd"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:car-check-20-bold" {...props}></Icon>
