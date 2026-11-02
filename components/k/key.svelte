<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/c/c61o_l6dm.css';
import '../../css/t/t0hxc5dvj.css';
import '../../css/m/mx_eqp0lm.css';
import '../../css/n/nb0c9bclg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="c61o_l6dm"/><path class="t0hxc5dvj"/><path class="mx_eqp0lm"/><path class="nb0c9bclg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:key" {...props}></Icon>
