<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8jt_mb0e.css';
import '../../css/k/kga35kgyc.css';
import '../../css/z/z5kh--bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8jt_mb0e"/><path class="kga35kgyc"/><path class="z5kh--bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:abacus-48" {...props}></Icon>
