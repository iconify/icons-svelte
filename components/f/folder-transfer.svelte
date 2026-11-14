<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s30cxiwcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s30cxiwcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-transfer" {...props}></Icon>
