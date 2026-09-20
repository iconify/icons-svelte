<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_w11wfxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l_w11wfxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:diamond-1-solid" {...props}></Icon>
