<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ows--s8kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ows--s8kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:last-fm-light" {...props}></Icon>
