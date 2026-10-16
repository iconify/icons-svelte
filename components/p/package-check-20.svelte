<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtjw67ppi.css';
import '../../css/m/m-ue7vdss.css';
import '../../css/m/mc34kf5uc.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rtjw67ppi"/><path class="m-ue7vdss"/><path class="mc34kf5uc"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:package-check-20" {...props}></Icon>
