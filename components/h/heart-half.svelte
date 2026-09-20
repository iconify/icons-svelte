<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc3w11iqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc3w11iqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-half" {...props}></Icon>
