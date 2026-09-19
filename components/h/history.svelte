<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0tfvsbut.css';
import '../../css/q/qc7bzg-vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0tfvsbut"/><path class="qc7bzg-vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:history" {...props}></Icon>
