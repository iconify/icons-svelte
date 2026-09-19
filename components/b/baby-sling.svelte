<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/w/w370i_-ni.css';
import '../../css/p/pk-427wln.css';
import '../../css/u/ub7r5_brs.css';
import '../../css/t/tsqrdnb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="w370i_-ni"/><path class="pk-427wln"/><path class="ub7r5_brs"/><path class="tsqrdnb5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:baby-sling" {...props}></Icon>
