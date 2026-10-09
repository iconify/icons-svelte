<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s57ieff-v.css';
import '../../css/l/lf0d-y9oh.css';
import '../../css/x/xqdmtubva.css';
import '../../css/l/lpc58nnfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s57ieff-v"/><path class="lf0d-y9oh"/><path class="xqdmtubva"/><path class="lpc58nnfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coral-20-bold" {...props}></Icon>
