<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkgs06hvj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/da92j5b5b.css';
import '../../css/p/po22q14_l.css';
import '../../css/p/pupu9ccnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkgs06hvj secondary"/><g class="dt0cm9dhy primary"><path class="da92j5b5b"/><path class="po22q14_l"/><path class="pupu9ccnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-alert-duo" {...props}></Icon>
