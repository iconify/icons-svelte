<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp8f-fbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pp8f-fbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ffxf-dark" {...props}></Icon>
