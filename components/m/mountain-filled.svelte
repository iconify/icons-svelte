<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctmm-bcwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctmm-bcwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mountain-filled" {...props}></Icon>
