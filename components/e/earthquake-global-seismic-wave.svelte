<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/olrq7wj0g.css';
import '../../css/z/zj2c36nlr.css';
import '../../css/l/lhd9qz21x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olrq7wj0g"/><path class="zj2c36nlr"/><path class="lhd9qz21x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:earthquake-global-seismic-wave" {...props}></Icon>
