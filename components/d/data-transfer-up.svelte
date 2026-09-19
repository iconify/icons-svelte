<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq04ipdji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rq04ipdji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:data-transfer-up" {...props}></Icon>
