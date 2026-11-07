<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mm_litbye.css';
import '../../css/l/l68gd2b_u.css';
import '../../css/u/utklsfbvf.css';
import '../../css/p/piipinbcz.css';
import '../../css/k/kkehyzd5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mm_litbye"/><path class="l68gd2b_u"/><path class="utklsfbvf"/><path class="piipinbcz"/><path class="kkehyzd5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:condicioner-line-duotone" {...props}></Icon>
