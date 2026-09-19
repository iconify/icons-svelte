<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfqe5lbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vfqe5lbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-from-right" {...props}></Icon>
