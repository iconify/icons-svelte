<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8d9-acuv.css';
import '../../css/t/t3nsxqbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8d9-acuv"/><path class="t3nsxqbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dosimeter-48-bold" {...props}></Icon>
