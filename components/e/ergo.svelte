<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfv2_eccz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cfv2_eccz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ergo" {...props}></Icon>
