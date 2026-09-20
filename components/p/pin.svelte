<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg75l3p3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yg75l3p3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:pin" {...props}></Icon>
