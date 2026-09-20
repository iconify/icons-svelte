<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzxl6r1_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qzxl6r1_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kiroshi-dark" {...props}></Icon>
