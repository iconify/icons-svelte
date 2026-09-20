<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3b1-vbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q3b1-vbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:graph-arrow-increase-flat" {...props}></Icon>
