<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp0j7gbhl.css';
import '../../css/c/cmyso5bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lp0j7gbhl"/><path class="cmyso5bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:campfire-fill" {...props}></Icon>
