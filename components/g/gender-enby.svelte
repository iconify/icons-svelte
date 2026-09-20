<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp_tq7kpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp_tq7kpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gender-enby" {...props}></Icon>
