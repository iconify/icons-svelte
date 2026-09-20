<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pis88xbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pis88xbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flip-vertical-circle-1" {...props}></Icon>
