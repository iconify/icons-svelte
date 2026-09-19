<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi827uptv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="fi827uptv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:inbox" {...props}></Icon>
