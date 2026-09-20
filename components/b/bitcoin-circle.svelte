<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0m5hyblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0m5hyblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bitcoin-circle" {...props}></Icon>
