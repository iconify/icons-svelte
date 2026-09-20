<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4zwn-thk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w4zwn-thk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bell" {...props}></Icon>
