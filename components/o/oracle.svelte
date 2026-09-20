<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb3z4vbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb3z4vbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:oracle" {...props}></Icon>
