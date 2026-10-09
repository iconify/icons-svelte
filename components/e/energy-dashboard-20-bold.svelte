<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf1ji9q9l.css';
import '../../css/u/uhr4-1blb.css';
import '../../css/p/pwxyecb7m.css';
import '../../css/k/k06yp_3mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mf1ji9q9l"/><path class="uhr4-1blb"/><path class="pwxyecb7m"/><path class="k06yp_3mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-dashboard-20-bold" {...props}></Icon>
