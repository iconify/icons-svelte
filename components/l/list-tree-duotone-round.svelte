<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aemvm93ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aemvm93ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-tree-duotone-round" {...props}></Icon>
