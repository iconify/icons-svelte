<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayw6rtddd.css';
import '../../css/e/e-psi4b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ayw6rtddd"/><path class="e-psi4b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:chart-pie" {...props}></Icon>
