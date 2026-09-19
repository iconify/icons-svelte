<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpfslacob.css';
import '../../css/d/dq9_gaclr.css';
import '../../css/c/clvzc9bjd.css';
import '../../css/v/vciy_oxlq.css';
import '../../css/n/nge6tfbxp.css';
import '../../css/p/pl74cqb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="gpfslacob"/><circle class="dq9_gaclr"/><circle class="clvzc9bjd"/><circle class="vciy_oxlq"/><circle class="nge6tfbxp"/><path class="pl74cqb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:qq-plot" {...props}></Icon>
