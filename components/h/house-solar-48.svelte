<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwp3j2jcs.css';
import '../../css/k/k_v0rcc0n.css';
import '../../css/u/usnws24vp.css';
import '../../css/b/bksa0ub5k.css';
import '../../css/f/fy4c6vbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uwp3j2jcs"/><path class="k_v0rcc0n"/><path class="usnws24vp"/><path class="bksa0ub5k"/><path class="fy4c6vbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-solar-48" {...props}></Icon>
