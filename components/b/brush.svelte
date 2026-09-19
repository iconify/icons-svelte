<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi4mg4ubu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="zi4mg4ubu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brush" {...props}></Icon>
