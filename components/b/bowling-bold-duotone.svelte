<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/q/qhrokpb5f.css';
import '../../css/k/kr6tfbc9g.css';
import '../../css/h/ht1vpi3ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="qhrokpb5f"/><path class="kr6tfbc9g"/><path class="ht1vpi3ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bowling-bold-duotone" {...props}></Icon>
