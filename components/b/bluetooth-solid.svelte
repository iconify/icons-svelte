<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lte55sbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lte55sbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bluetooth-solid" {...props}></Icon>
