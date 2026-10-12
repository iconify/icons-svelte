<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rne8-kbom.css';
import '../../css/z/zhnptnbwx.css';
import '../../css/g/gp9p8lb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rne8-kbom"/><path class="zhnptnbwx"/><path class="gp9p8lb5v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:faucet-duotone" {...props}></Icon>
