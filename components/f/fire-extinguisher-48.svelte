<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m24wi8bnz.css';
import '../../css/n/ntd2yfzrm.css';
import '../../css/b/bi_k8i90y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m24wi8bnz"/><path class="ntd2yfzrm"/><path class="bi_k8i90y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-extinguisher-48" {...props}></Icon>
