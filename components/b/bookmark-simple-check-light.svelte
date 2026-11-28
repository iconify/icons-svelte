<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnm38wbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pnm38wbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-check-light" {...props}></Icon>
