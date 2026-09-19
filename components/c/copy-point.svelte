<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nda5gnl9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nda5gnl9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:copy-point" {...props}></Icon>
