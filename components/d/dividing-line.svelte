<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n08ut8bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n08ut8bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dividing-line" {...props}></Icon>
