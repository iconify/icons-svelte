<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/mi0gayb5c.css';
import '../../css/n/nmv9v_bkx.css';
import '../../css/f/fmr0e_lvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mi0gayb5c"/><path class="nmv9v_bkx"/><path class="fmr0e_lvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:coin" {...props}></Icon>
