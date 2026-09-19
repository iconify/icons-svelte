<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvg6d5bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gvg6d5bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:heart-circle-xmark" {...props}></Icon>
