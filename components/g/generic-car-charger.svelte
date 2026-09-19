<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm-x0nboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm-x0nboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:generic-car-charger" {...props}></Icon>
