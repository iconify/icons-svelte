<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_q9sfwij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f_q9sfwij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:capacity-pen-filled" {...props}></Icon>
