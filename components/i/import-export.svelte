<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr5g2_dys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="rr5g2_dys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:import-export" {...props}></Icon>
