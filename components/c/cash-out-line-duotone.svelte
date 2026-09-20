<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n_6kqbh0h.css';
import '../../css/a/aurb_obnv.css';
import '../../css/i/i-b1b9mbj.css';
import '../../css/m/mssc0fbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n_6kqbh0h"/><path class="aurb_obnv"/><path class="i-b1b9mbj"/><path class="mssc0fbma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cash-out-line-duotone" {...props}></Icon>
