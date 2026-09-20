<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jmv2f3b2c.css';
import '../../css/r/rp05lmnnc.css';
import '../../css/v/v_mzr6b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmv2f3b2c"/><path class="rp05lmnnc"/><path class="v_mzr6b6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music3" {...props}></Icon>
