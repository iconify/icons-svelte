<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkk820mfz.css';
import '../../css/w/w2_kf1b2m.css';
import '../../css/k/k-ajidckb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hkk820mfz"/><path class="w2_kf1b2m"/><path class="k-ajidckb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-48" {...props}></Icon>
