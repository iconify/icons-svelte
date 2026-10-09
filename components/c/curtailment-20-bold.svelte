<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc7msjb7m.css';
import '../../css/b/bdgh64buo.css';
import '../../css/g/gxsgqfbzc.css';
import '../../css/q/qnfhe3b6k.css';
import '../../css/t/trfzb5bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oc7msjb7m"/><path class="bdgh64buo"/><path class="gxsgqfbzc"/><path class="qnfhe3b6k"/><path class="trfzb5bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:curtailment-20-bold" {...props}></Icon>
