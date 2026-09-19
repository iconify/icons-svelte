<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxwh64lzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lxwh64lzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:code-bracket-square-20-solid" {...props}></Icon>
