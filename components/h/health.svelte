<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv2ls5b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gv2ls5b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:health" {...props}></Icon>
