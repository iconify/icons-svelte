<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/eosf8ub_j.css';
import '../../css/l/lhivpe_dj.css';
import '../../css/p/p-mz6wbtp.css';
import '../../css/d/d49nub01a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="eosf8ub_j"/><path class="lhivpe_dj"/><path class="p-mz6wbtp"/><path class="d49nub01a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drafting-compass" {...props}></Icon>
