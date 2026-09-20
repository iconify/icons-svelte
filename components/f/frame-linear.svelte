<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/raqzb_bqt.css';
import '../../css/b/beu8enohc.css';
import '../../css/u/uzjzslbbw.css';
import '../../css/o/oqpf2r_po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="raqzb_bqt"/><path class="beu8enohc"/><path class="uzjzslbbw"/><path class="oqpf2r_po"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:frame-linear" {...props}></Icon>
