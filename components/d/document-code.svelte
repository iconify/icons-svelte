<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr10dfbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wr10dfbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-code" {...props}></Icon>
