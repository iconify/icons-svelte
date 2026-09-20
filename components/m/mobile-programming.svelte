<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qd4wafbbv.css';
import '../../css/l/lwpz82cdv.css';
import '../../css/x/xi-jxcbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qd4wafbbv"/><path class="lwpz82cdv"/><path class="xi-jxcbdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mobile-programming" {...props}></Icon>
