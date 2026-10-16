<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umayoyb1k.css';
import '../../css/o/ocq2nsbni.css';
import '../../css/z/zr0me355o.css';
import '../../css/b/besblbm2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="umayoyb1k"/><path class="ocq2nsbni"/><path class="zr0me355o"/><path class="besblbm2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-polar-20-bold" {...props}></Icon>
