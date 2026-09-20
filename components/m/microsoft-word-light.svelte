<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yftarabyl.css';
import '../../css/q/qxihk5bwn.css';
import '../../css/k/knu7vdbvo.css';
import '../../css/o/ofhs6z3pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yftarabyl"/><path class="qxihk5bwn"/><path class="knu7vdbvo"/><path class="ofhs6z3pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-word-light" {...props}></Icon>
