<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnsr8kbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lnsr8kbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qdirstat-light" {...props}></Icon>
