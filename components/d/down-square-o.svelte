<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc6nfyonh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pc6nfyonh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:down-square-o" {...props}></Icon>
