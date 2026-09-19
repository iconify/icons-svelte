<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud8u_abuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ud8u_abuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:paypal" {...props}></Icon>
