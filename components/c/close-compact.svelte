<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na7ncnoxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="na7ncnoxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:close-compact" {...props}></Icon>
