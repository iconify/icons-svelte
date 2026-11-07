<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/r0fjgcb6p.css';
import '../../css/h/h0rtdjbeb.css';
import '../../css/n/ndcdy4d6d.css';
import '../../css/z/zvfketbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r0fjgcb6p"/><path class="h0rtdjbeb"/><path class="ndcdy4d6d"/><path class="zvfketbhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plug-circle-line-duotone" {...props}></Icon>
