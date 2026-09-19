<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhb_aqb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qhb_aqb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cloudscale" {...props}></Icon>
