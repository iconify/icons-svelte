<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv69e6bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gv69e6bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plumio-light" {...props}></Icon>
