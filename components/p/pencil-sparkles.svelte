<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt8gb5tzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt8gb5tzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pencil-sparkles" {...props}></Icon>
