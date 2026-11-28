<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb9pkpb7b.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wcdchccgf.css';
import '../../css/t/tgl67pb8o.css';
import '../../css/a/a_wq3zl0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb9pkpb7b secondary"/><g class="dt0cm9dhy primary"><path class="wcdchccgf"/><circle class="tgl67pb8o"/><circle class="a_wq3zl0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:percent-duo" {...props}></Icon>
