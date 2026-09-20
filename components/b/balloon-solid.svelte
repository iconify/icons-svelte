<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5uxynb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w5uxynb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:balloon-solid" {...props}></Icon>
