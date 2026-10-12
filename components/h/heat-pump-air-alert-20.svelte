<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu5haub2l.css';
import '../../css/q/qnea9bsmy.css';
import '../../css/j/j6cyu6bqi.css';
import '../../css/p/p-qkgzbzb.css';
import '../../css/k/k_yv9qbfm.css';
import '../../css/n/nq5_p_bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wu5haub2l"/><path class="qnea9bsmy"/><path class="j6cyu6bqi"/><path class="p-qkgzbzb"/><path class="k_yv9qbfm"/><path class="nq5_p_bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-air-alert-20" {...props}></Icon>
