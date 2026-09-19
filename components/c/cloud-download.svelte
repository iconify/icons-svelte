<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr6fn7b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="wr6fn7b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cloud-download" {...props}></Icon>
