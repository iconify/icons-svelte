<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrjr88hvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrjr88hvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:phone" {...props}></Icon>
