<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kaw7birim.css';
import '../../css/v/vk3y0vbad.css';
import '../../css/f/fc1qebbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kaw7birim"/><path class="vk3y0vbad"/><path class="fc1qebbtl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:like-shapes" {...props}></Icon>
