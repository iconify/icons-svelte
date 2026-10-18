<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5f9s_k4f.css';
import '../../css/o/oc7x2x87v.css';
import '../../css/k/kcpt-5ssg.css';
import '../../css/h/hoiq_la6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q5f9s_k4f"/><path class="oc7x2x87v"/><path class="kcpt-5ssg"/><path class="hoiq_la6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cybersecurity-20-bold" {...props}></Icon>
