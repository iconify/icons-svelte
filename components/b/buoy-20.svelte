<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdl5g5dgd.css';
import '../../css/e/e2ii3_num.css';
import '../../css/h/hq8tc3ygq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vdl5g5dgd"/><path class="e2ii3_num"/><path class="hq8tc3ygq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:buoy-20" {...props}></Icon>
