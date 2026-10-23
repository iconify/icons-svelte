<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2dtuibau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2dtuibau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map-pin-x" {...props}></Icon>
