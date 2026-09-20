<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iee-akbkn.css';
import '../../css/o/o10soq-vv.css';
import '../../css/m/mi28tkziw.css';
import '../../css/l/l56cuebno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="iee-akbkn"/><path class="o10soq-vv"/><path class="mi28tkziw"/><path class="l56cuebno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-genetics" {...props}></Icon>
