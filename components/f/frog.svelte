<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dalgnjpdy.css';
import '../../css/v/vrunflstg.css';
import '../../css/x/xh5iej9vb.css';
import '../../css/e/eqpexpb_m.css';
import '../../css/y/yj617eybb.css';
import '../../css/t/tnolhfsay.css';
import '../../css/p/pl33t8bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dalgnjpdy"/><path class="vrunflstg"/><path class="xh5iej9vb"/><circle class="eqpexpb_m"/><circle class="yj617eybb"/><circle class="tnolhfsay"/><circle class="pl33t8bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:frog" {...props}></Icon>
