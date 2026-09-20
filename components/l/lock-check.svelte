<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxfg4pqzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pxfg4pqzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:lock-check" {...props}></Icon>
