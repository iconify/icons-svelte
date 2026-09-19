<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlj_ihbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xlj_ihbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-sad" {...props}></Icon>
