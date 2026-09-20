<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrxu82zuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrxu82zuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:eyedropper" {...props}></Icon>
