<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af-a9mxeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="af-a9mxeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:prescription" {...props}></Icon>
