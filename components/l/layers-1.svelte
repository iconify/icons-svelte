<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-71xacun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i-71xacun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:layers-1" {...props}></Icon>
