<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn29nlyjq.css';
import '../../css/u/uktn-1b8e.css';
import '../../css/x/xm5em6khk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tn29nlyjq"/><path class="uktn-1b8e"/><path class="xm5em6khk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-check-20" {...props}></Icon>
