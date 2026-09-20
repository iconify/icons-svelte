<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku0n0gbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku0n0gbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-dollar" {...props}></Icon>
