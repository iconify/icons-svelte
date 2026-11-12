<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxuo7eb7y.css';
import '../../css/g/gin1cnjoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uxuo7eb7y"/><path class="gin1cnjoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-translate-light" {...props}></Icon>
