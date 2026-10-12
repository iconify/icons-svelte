<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv2urftea.css';
import '../../css/p/p03glfbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv2urftea"/><path clip-rule="evenodd" class="p03glfbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:face-grinning-filled" {...props}></Icon>
