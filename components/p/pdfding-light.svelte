<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7v6wxb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w7v6wxb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pdfding-light" {...props}></Icon>
