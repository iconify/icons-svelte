<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meonpbcpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="meonpbcpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-left-design-flip-reflect-left-horizontal" {...props}></Icon>
