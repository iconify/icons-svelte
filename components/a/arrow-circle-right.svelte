<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afci7hbne.css';
import '../../css/g/g1m3d2bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="afci7hbne"/><path class="g1m3d2bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-circle-right" {...props}></Icon>
