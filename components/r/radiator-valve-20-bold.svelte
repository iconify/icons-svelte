<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjaxhlnkd.css';
import '../../css/v/vlwm4ybiy.css';
import '../../css/l/lpnx10b3p.css';
import '../../css/q/qho2-b78i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yjaxhlnkd"/><path class="vlwm4ybiy"/><path class="lpnx10b3p"/><path class="qho2-b78i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiator-valve-20-bold" {...props}></Icon>
