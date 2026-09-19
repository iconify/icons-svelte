<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvoln-qjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bvoln-qjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:angular" {...props}></Icon>
