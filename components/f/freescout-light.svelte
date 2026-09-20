<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxbz4umia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxbz4umia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freescout-light" {...props}></Icon>
