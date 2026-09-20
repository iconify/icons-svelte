<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzx2bp9nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzx2bp9nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cerbos-dark" {...props}></Icon>
