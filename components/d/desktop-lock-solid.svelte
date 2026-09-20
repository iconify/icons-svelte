<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrer5irbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zrer5irbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:desktop-lock-solid" {...props}></Icon>
