<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re0svb5xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re0svb5xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pdfding-dark" {...props}></Icon>
