<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3we5pccv.css';
import '../../css/t/tli6u_ttm.css';
import '../../css/b/b7ri4q8vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3we5pccv"/><path class="tli6u_ttm"/><path class="b7ri4q8vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:riceball" {...props}></Icon>
