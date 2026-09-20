<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orlvco9_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="orlvco9_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bold-l" {...props}></Icon>
