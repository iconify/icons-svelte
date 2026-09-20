<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv322cbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zv322cbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:drone-solid" {...props}></Icon>
