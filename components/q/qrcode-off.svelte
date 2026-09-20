<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1d6mib0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1d6mib0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:qrcode-off" {...props}></Icon>
