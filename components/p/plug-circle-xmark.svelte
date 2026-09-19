<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gygm8dbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gygm8dbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plug-circle-xmark" {...props}></Icon>
