<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bet7e2qhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bet7e2qhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:network-device-filled" {...props}></Icon>
