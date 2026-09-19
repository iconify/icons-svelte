<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1dnwesbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n1dnwesbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-ol-rtl" {...props}></Icon>
