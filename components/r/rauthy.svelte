<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwpo4xbeq.css';
import '../../css/o/ofc_1ckbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwpo4xbeq"/><path class="ofc_1ckbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rauthy" {...props}></Icon>
