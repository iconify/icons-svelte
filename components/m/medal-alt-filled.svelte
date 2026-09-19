<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ethc65zvb.css';
import '../../css/p/pkygmcb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ethc65zvb"/><path class="pkygmcb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-alt-filled" {...props}></Icon>
