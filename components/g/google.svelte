<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1f2wrbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":512};
const content = `<path class="g1f2wrbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:google" {...props}></Icon>
