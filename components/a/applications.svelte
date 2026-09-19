<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8qlosbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8qlosbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:applications" {...props}></Icon>
