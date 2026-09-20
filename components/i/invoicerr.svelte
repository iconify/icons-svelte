<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtyr96uhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xtyr96uhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoicerr" {...props}></Icon>
