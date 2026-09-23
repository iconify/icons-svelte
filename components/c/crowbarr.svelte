<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv4dbmbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vv4dbmbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowbarr" {...props}></Icon>
