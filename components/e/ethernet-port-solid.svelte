<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o505lachm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o505lachm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ethernet-port-solid" {...props}></Icon>
