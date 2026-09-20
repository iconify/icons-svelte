<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drtpar3pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drtpar3pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:location-pin" {...props}></Icon>
