<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy_n96oom.css';
import '../../css/t/tq3jfobxa.css';
import '../../css/e/e58540bzj.css';
import '../../css/w/w3ursc5fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jy_n96oom"/><path class="tq3jfobxa"/><path class="e58540bzj"/><path class="w3ursc5fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fertiliser-48" {...props}></Icon>
