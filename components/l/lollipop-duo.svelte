<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfg_f7bxl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r78i7gkxp.css';
import '../../css/b/bnwu_lbuf.css';
import '../../css/f/fwq3qmi6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary vfg_f7bxl"/><g class="dt0cm9dhy primary"><path class="r78i7gkxp"/><path class="bnwu_lbuf"/><path class="fwq3qmi6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lollipop-duo" {...props}></Icon>
