<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di9mx7u9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di9mx7u9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:filter-3-line" {...props}></Icon>
