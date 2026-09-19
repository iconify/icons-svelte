<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgtxsdbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="cgtxsdbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plus-2" {...props}></Icon>
