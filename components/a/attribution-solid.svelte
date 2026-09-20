<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyymi3ddh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyymi3ddh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:attribution-solid" {...props}></Icon>
